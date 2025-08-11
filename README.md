import Image from 'next/image';

export default function HeaderCapsule() {
  return (
    <Image
      src="https://capsule-render.vercel.app/api?type=waving&height=300&color=gradient&text=Your+Text+Here&descAlign=49"
      alt="Animated Capsule Header"
      width={600}
      height={300}
    />
  );
}
